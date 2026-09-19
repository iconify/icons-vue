<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j49hvua4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j49hvua4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:flask-solid" /></template>
