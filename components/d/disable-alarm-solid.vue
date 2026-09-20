<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ids8rjbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ids8rjbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:disable-alarm-solid" /></template>
