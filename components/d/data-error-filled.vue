<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnuozhkls.css';
import '../../css/o/ob_wxib3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="bnuozhkls"/><path class="ob_wxib3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:data-error-filled" /></template>
