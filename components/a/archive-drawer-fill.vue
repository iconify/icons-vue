<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bitppkb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bitppkb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:archive-drawer-fill" /></template>
