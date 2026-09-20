<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo8tknqau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo8tknqau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-minus-sharp" /></template>
