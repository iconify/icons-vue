<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mww2knb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mww2knb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-up-sharp" /></template>
