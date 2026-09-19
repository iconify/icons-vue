<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b73k0pm-y.css';
import '../../css/v/v1qktebkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b73k0pm-y"/><path clip-rule="evenodd" class="v1qktebkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:document-outline" /></template>
