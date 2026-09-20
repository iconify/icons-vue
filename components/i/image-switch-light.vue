<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yagq6hbek.css';
import '../../css/f/f6k8znems.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yagq6hbek"/><path class="f6k8znems"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-switch-light" /></template>
