<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3-jnqb4z.css';
import '../../css/c/c7wml7kwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o3-jnqb4z"/><path class="c7wml7kwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:mail-outgoing-solid" /></template>
