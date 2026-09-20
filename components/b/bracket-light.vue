<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfamlxbej.css';
import '../../css/l/lwt7zu3on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dfamlxbej"/><path class="lwt7zu3on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bracket-light" /></template>
