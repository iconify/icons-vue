<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz1nq5bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hz1nq5bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-vagrant-dark" /></template>
