<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlq4-ewtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlq4-ewtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:booze" /></template>
