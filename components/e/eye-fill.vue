<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siux78bid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="siux78bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:eye-fill" /></template>
