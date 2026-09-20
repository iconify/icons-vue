<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-d5ipbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-d5ipbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:credit-card-solid" /></template>
