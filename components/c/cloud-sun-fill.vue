<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbu6-s_cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jbu6-s_cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud-sun-fill" /></template>
