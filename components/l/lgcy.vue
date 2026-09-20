<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcwroccto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcwroccto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lgcy" /></template>
