<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmevdnb3h.css';
import '../../css/b/bw323sqaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmevdnb3h"/><path class="bw323sqaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:city" /></template>
