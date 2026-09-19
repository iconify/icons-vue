<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kti7wod0f.css';
import '../../css/b/b2126bb3z.css';
import '../../css/p/pet3n157a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kti7wod0f"/><path class="b2126bb3z"/><path class="pet3n157a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:iot" /></template>
