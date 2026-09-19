<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa-4lbc2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="aa-4lbc2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:checkmark-shield-fill" /></template>
