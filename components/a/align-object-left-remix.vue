<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6rqx6bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="m6rqx6bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:align-object-left-remix" /></template>
