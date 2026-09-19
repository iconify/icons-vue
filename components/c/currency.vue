<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgakgacod.css';
import '../../css/s/s0oh6wb6v.css';
import '../../css/m/mfmbc9s1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25.9,"height":16.8};
const content = `<path class="cgakgacod"/><path class="s0oh6wb6v"/><path class="mfmbc9s1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:currency" /></template>
