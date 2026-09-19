<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua12k1jnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ua12k1jnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:info-square" /></template>
