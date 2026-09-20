<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eme4hnzwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eme4hnzwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chevron-up-double" /></template>
