<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a27xsi6vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a27xsi6vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:battery-low" /></template>
