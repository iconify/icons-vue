<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbvt165ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbvt165ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:briefcase" /></template>
