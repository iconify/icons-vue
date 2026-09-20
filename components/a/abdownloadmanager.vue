<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcnb0lbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcnb0lbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:abdownloadmanager" /></template>
