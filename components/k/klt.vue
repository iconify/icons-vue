<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGG8S6JeFP)" clip-rule="evenodd" class="erunf9bgd"/><defs><linearGradient id="SVGG8S6JeFP" x1="20.394" x2="3.27" y1="10.053" y2="10.053" gradientUnits="userSpaceOnUse"><stop offset=".12" class="f-mh4mr2d"/><stop offset="1" class="c8q_4prir"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:klt" /></template>
<style>
.c8q_4prir {
  stop-color: var(--svg-color--0aaef3, #0aaef3);
}

.erunf9bgd {
  fill-rule: evenodd;
  d: path("M15.235 5.605h-.867v1.8c-.757-.625-2.065-1.326-3.836-1.326h-.08a6.02 6.02 0 0 0-5.363 3.315H3v1.422h1.577q-.156.669-.156 1.387c0 3.42 2.728 6.192 6.101 6.192h.246c1.388 0 2.511-1.142 2.511-2.549v-.152a2.464 2.464 0 0 0-2.444-2.482h-.228a2.07 2.07 0 0 0-1.875 1.208c-.218.464.217.9.73.9c.226 0 .406-.199.51-.402a.86.86 0 0 1 .763-.474h.11a1.113 1.113 0 0 1 1.108 1.127v.29c0 .662-.53 1.207-1.185 1.207h-.345a4.74 4.74 0 0 1-4.676-4.784c0-.507.076-1.004.218-1.469H21v-1.42h-1.9c-.123-2.113-1.804-3.79-3.865-3.79m-.71 3.79c-1.232-1.71-2.999-2.123-3.804-2.104h-.09c-1.639 0-3.088.834-3.979 2.103zm3.368 0h-2.104v-2.36l.162.034c1.136.218 1.837 1.18 1.942 2.325");
}

.f-mh4mr2d {
  stop-color: var(--svg-color--a157fd, #a157fd);
}

.ft5dv1b6b {
  fill: none;
}

</style>
