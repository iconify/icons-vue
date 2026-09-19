<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwylhvbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xwylhvbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-card-protection-alt" /></template>
