<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr1duizkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fr1duizkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:lineage-logo-solid" /></template>
