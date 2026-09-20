<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8xd7l3mw.css';
import '../../css/e/emm9ff-2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q8xd7l3mw"/><path clip-rule="evenodd" class="emm9ff-2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:attachment-solid" /></template>
