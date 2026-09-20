<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3t0lctow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="k3t0lctow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:location-pin-disabled-solid" /></template>
