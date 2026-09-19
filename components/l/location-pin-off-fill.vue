<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx9xeebvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xx9xeebvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:location-pin-off-fill" /></template>
