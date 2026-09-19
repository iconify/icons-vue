<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm3i78bcl.css';
import '../../css/d/d0bz8sb9m.css';
import '../../css/z/zzlmo8aoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm3i78bcl"/><path class="d0bz8sb9m"/><path class="zzlmo8aoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:confused" /></template>
