<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em3p83bvs.css';
import '../../css/a/a7uahqbqs.css';
import '../../css/b/bqzidgs3h.css';
import '../../css/n/nrkqveb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em3p83bvs"/><path clip-rule="evenodd" class="a7uahqbqs"/><path class="bqzidgs3h"/><path class="nrkqveb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:jar-of-pills-bold" /></template>
