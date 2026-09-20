<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejki_ob7b.css';
import '../../css/i/igx7fitry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejki_ob7b"/><path class="igx7fitry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:git-repository-commits-filled" /></template>
