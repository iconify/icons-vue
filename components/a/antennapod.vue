<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejpquccgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejpquccgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:antennapod" /></template>
