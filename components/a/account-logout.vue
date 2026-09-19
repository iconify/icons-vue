<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rak8y7bfa.css';
import '../../css/o/o3-o5nogz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rak8y7bfa"/><path class="o3-o5nogz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:account-logout" /></template>
