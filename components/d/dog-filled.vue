<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecejspz5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecejspz5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dog-filled" /></template>
