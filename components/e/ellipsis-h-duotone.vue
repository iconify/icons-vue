<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx93t8bdb.css';
import '../../css/b/bj2qr51xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mx93t8bdb"/><path clip-rule="evenodd" class="bj2qr51xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:ellipsis-h-duotone" /></template>
