<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waq7ozb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waq7ozb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:edit-filled" /></template>
