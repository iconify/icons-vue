<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk_cz7sof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="qk_cz7sof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:firewire" /></template>
