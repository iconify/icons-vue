<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcce5mspk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcce5mspk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:criminal-fill" /></template>
