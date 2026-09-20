<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehxg8b96x.css';
import '../../css/y/yhh61y7yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ehxg8b96x"/><path clip-rule="evenodd" class="yhh61y7yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:angular-solid" /></template>
