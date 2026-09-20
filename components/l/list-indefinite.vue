<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijx9o5bpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijx9o5bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:list-indefinite" /></template>
