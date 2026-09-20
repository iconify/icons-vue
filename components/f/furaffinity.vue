<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsrxc5b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsrxc5b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:furaffinity" /></template>
