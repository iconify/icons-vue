<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3w0jnb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3w0jnb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:flag-alt-3-fill" /></template>
