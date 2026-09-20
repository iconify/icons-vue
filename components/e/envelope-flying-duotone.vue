<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jouqagfwy.css';
import '../../css/s/sugl59zus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jouqagfwy"/><path class="sugl59zus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:envelope-flying-duotone" /></template>
