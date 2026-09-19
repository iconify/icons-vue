<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x30i7ibvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x30i7ibvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-card-check-alt-filled" /></template>
