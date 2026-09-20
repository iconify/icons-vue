<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo3v1db4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo3v1db4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-offset-right-fill" /></template>
