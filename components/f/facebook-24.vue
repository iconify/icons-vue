<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyr05pb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pyr05pb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:facebook-24" /></template>
