<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li8oa0riw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="li8oa0riw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:lock-open-1" /></template>
