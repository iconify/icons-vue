<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urbb0o_je.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urbb0o_je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-plus" /></template>
