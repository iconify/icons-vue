<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4bk5tbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n4bk5tbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:lock-solid" /></template>
