<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="d4xddsb4n"/><path class="stzv1kigp"/><g class="hgqw6lb7c"><path class="c5-uhm0na"/><path class="x0oicpb9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:alien-monster" /></template>
<style>
.c5-uhm0na {
  d: path("M19.694 10h4.921v4.923h-4.921zm19.686 0h4.921v4.923H39.38zM4.923 24.698h4.924v4.922H4.923zM24.616 49.21h4.923v4.921h-4.923zm9.845 0h4.924v4.921h-4.924z");
}

.d4xddsb4n {
  fill: var(--svg-color--242c62, #242c62);
  d: path("M19.694 34.543h4.921v4.921h-4.921zm14.767 0h4.924v4.921h-4.924z");
}

.hgqw6lb7c {
  fill: var(--svg-color--69c9f2, #69c9f2);
}

.stzv1kigp {
  fill: var(--svg-color--fff, #fff);
  d: path("M29.539 34.543V29.62h-9.845v4.923h4.922v4.921h4.923zm14.771 4.921V29.62h-9.849v4.923h4.919v4.921z");
}

.x0oicpb9t {
  d: path("M59.08 49.21v-4.924h-4.923V39.46h-4.922v-4.921h4.922v-4.853h4.923v-4.922h-4.923v4.851h-4.922v-4.922h-4.926v-4.852h-4.921v-4.922h-4.924v4.922h-4.922v-4.922h-4.923v4.922h-4.921v4.853h-4.926v4.922H9.851v4.923h4.921v4.921H9.851v4.826H4.927v4.924H.004v4.921h9.847V49.21h4.921v-4.826h4.926v4.826h4.921v-4.826h14.769v4.826h4.921v-4.826h4.926v4.826h4.922v4.921h9.847V49.21zm-34.46-9.75h-4.921v-9.844h9.844v9.844zm14.769 0h-4.924v-9.844h9.845v9.844z");
}

</style>
