<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa7q40b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa7q40b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-7-sharp-fill" /></template>
