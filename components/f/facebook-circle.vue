<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw_-6tbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw_-6tbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:facebook-circle" /></template>
