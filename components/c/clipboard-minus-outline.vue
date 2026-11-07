<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3cnu0b3i.css';
import '../../css/e/e3rn21oia.css';
import '../../css/e/e67e0wblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3cnu0b3i"/><path class="e3rn21oia"/><path class="e67e0wblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-minus-outline" /></template>
