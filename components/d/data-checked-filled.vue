<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnuozhkls.css';
import '../../css/s/s1i3vlbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="bnuozhkls"/><path class="s1i3vlbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:data-checked-filled" /></template>
