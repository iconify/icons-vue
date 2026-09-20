<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcn5smb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcn5smb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-up-line" /></template>
