<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf6cjrb9y.css';
import '../../css/e/egk9jea5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf6cjrb9y"/><path clip-rule="evenodd" class="egk9jea5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-check-outline" /></template>
