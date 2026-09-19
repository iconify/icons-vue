<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvnsb8bex.css';
import '../../css/r/rjfhlsb4c.css';
import '../../css/o/o235c4b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dvnsb8bex"/><path class="rjfhlsb4c"/><path class="o235c4b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:android-os" /></template>
