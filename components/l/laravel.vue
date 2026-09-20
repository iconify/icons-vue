<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tysy9demy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tysy9demy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:laravel" /></template>
