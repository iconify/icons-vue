<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl4vnpthx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bl4vnpthx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:building-alt-02-filled" /></template>
