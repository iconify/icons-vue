<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bar7fkprl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bar7fkprl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:blank-notepad-solid" /></template>
