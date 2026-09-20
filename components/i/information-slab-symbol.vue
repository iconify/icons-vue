<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bie8y9lpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bie8y9lpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:information-slab-symbol" /></template>
