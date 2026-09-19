<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkfik5lax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="mkfik5lax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowtriangle-up-fill" /></template>
