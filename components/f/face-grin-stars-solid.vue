<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v16xx8pet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v16xx8pet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:face-grin-stars-solid" /></template>
