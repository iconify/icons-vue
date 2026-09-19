<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aixq4db0w.css';
import '../../css/d/deb9mesxm.css';
import '../../css/i/iwlahz8ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aixq4db0w"/><path class="deb9mesxm"/><path class="iwlahz8ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:document" /></template>
