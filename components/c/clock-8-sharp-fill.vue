<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1b6u2bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g1b6u2bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-8-sharp-fill" /></template>
