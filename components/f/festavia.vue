<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeyx6vbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aeyx6vbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:festavia" /></template>
