<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff8g36beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ff8g36beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lock-open-alt-02" /></template>
