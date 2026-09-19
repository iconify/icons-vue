<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5-90bbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k5-90bbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-card-cancel-alt-filled" /></template>
