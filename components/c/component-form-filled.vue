<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huh_2krav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="huh_2krav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:component-form-filled" /></template>
