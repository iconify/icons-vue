<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f31h5zbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f31h5zbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eye-closed-outline" /></template>
