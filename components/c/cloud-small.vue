<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eee2krb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="eee2krb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:cloud-small" /></template>
