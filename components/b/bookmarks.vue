<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7phojbjv.css';
import '../../css/o/ojlbdmb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7phojbjv"/><path class="ojlbdmb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bookmarks" /></template>
