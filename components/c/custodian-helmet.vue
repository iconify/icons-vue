<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu7e8zb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qu7e8zb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:custodian-helmet" /></template>
