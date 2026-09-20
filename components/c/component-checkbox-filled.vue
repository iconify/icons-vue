<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr2er1f5h.css';
import '../../css/z/z6ezkobko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr2er1f5h"/><path class="z6ezkobko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:component-checkbox-filled" /></template>
