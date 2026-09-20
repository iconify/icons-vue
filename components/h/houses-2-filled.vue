<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pac7fn7hq.css';
import '../../css/g/gl2fr07us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pac7fn7hq"/><path class="gl2fr07us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:houses-2-filled" /></template>
