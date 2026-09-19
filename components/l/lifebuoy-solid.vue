<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fly7y8bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fly7y8bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:lifebuoy-solid" /></template>
