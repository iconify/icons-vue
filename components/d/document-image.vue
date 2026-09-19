<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzbtv324v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzbtv324v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-image" /></template>
