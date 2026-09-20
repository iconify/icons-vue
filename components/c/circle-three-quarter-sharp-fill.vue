<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdvcix4ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sdvcix4ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-three-quarter-sharp-fill" /></template>
