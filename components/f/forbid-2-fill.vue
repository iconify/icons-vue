<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aciy-rbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aciy-rbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:forbid-2-fill" /></template>
