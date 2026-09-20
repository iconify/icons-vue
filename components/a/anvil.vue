<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc2cz1enc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rc2cz1enc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:anvil" /></template>
