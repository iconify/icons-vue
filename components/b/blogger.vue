<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b50jzdmup.css';
import '../../css/b/b1u2enx3s.css';
import '../../css/g/g3roa_mfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b50jzdmup"/><path class="b1u2enx3s"/><path class="g3roa_mfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:blogger" /></template>
