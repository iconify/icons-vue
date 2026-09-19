<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efi4ej_dk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efi4ej_dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:loader-lines-alt" /></template>
