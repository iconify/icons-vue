<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glg9711yw.css';
import '../../css/g/go1ki5bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="glg9711yw"/><path class="go1ki5bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:crop" /></template>
