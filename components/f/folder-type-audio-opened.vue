<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="flqdhbcaw"/><path class="uds6zz2lw"/><path class="hcunrbx0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-audio-opened" /></template>
<style>
.flqdhbcaw {
  fill: var(--svg-color--7b7bdb, #7b7bdb);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.hcunrbx0q {
  fill: var(--svg-color--00007f, #00007f);
  d: path("M21.422 13a.68.68 0 0 0-.427.174l-5.7 4.74a.87.87 0 0 1-.716.246h-3.673a.9.9 0 0 0-.906.894s0 .008 0 .012v5.87a.9.9 0 0 0 .9.9h3.68a.87.87 0 0 1 .716.246l5.7 4.74c.391.325.811.168.811-.217V13.391a.37.37 0 0 0-.354-.391Zm7.328 1.725l-1.343 1.345a11.03 11.03 0 0 1 0 11.883l1.339 1.332a12.89 12.89 0 0 0 .004-14.561Zm-3.25 3.241L24.179 19.3a4.53 4.53 0 0 1 0 5.428l1.321 1.316a6.416 6.416 0 0 0 .008-8.077Z");
}

.uds6zz2lw {
  fill: var(--svg-color--7b7bdb, #7b7bdb);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

</style>
