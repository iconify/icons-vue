<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smb8bhb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smb8bhb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-arrow-up-outline" /></template>
