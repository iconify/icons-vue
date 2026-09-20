<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqv0kxbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqv0kxbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:card-account-mail" /></template>
