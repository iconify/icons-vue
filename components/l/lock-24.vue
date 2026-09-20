<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twz5xh3ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="twz5xh3ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:lock-24" /></template>
