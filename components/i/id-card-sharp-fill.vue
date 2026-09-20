<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk32t904i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yk32t904i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:id-card-sharp-fill" /></template>
