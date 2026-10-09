<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvc9z5wej.css';
import '../../css/d/df3f56xlz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gvc9z5wej"/><path class="df3f56xlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cactus-48-bold" /></template>
