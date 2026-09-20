<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0y6itbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t0y6itbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chevron-up-solid" /></template>
