<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-9l2s4jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-9l2s4jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:keycloak" /></template>
