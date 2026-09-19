<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/e/e_iwscbqa.css';
import '../../css/i/i0ds1rbow.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxZaWXdHc"><g class="aql7dnt-u"><circle class="e_iwscbqa"/><path class="i0ds1rbow"/></g></mask></defs><path mask="url(#SVGxZaWXdHc)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:add-user" /></template>
