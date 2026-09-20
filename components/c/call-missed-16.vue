<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7w6s7b2e.css';
import '../../css/v/v5pqt5bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b7w6s7b2e"/><path class="v5pqt5bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:call-missed-16" /></template>
