<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rnkr-gbaj"/><path class="lk2uk2khl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-karma" /></template>
<style>
.lk2uk2khl {
  fill: var(--svg-color--56c5a8, #56c5a8);
  d: path("m5.154 23.659l4.946-8.932l-3.144 2.964l-5.029-5.935l3.228 11.9M29.28 5.122h-6.79l-4.158 6.144V5.122H12.1v6.372l3.321 12.239l.774 2.9h2.134v-5.379z");
}

.rnkr-gbaj {
  fill: var(--svg-color--429f87, #429f87);
  d: path("m18.842 20.224l4.295 6.407h6.79l-7.695-11.369l-3.39 4.961M5.154 23.659L8.3 20.7l5.028 5.934L10.1 14.727L7.374 19.21z");
}

</style>
