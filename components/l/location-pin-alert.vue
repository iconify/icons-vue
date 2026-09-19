<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5i58ebyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g5i58ebyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:location-pin-alert" /></template>
