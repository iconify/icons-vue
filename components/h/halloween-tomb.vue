<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jus2nxdev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jus2nxdev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:halloween-tomb" /></template>
