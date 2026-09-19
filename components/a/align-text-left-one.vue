<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/m/m2blynbna.css';
import '../../css/a/a_zfs7wna.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMHMLRb7Y"><g class="ufeehvblu"><path class="m2blynbna"/><path class="a_zfs7wna"/></g></mask></defs><path mask="url(#SVGMHMLRb7Y)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:align-text-left-one" /></template>
