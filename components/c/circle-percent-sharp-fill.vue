<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9ree0-jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m9ree0-jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-percent-sharp-fill" /></template>
