<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnffa9b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="mnffa9b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:googleglass" /></template>
