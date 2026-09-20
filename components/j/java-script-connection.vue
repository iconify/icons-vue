<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktkaqkbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ktkaqkbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:java-script-connection" /></template>
