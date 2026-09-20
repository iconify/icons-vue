<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="xcfhw0bzy"/><path class="vbxe0xtoi"/><path class="sex7xjoka"/><g clip-rule="evenodd" class="d2kvgvbvc"><path class="i4ttorblq"/><path class="c_ud8552l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-lesotho" /></template>
<style>
.c_ud8552l {
  fill: var(--svg-color--53646d, #53646d);
  d: path("M20.797 20.344s-1.422.526-2.797.526s-2.797-.526-2.797-.526l-.344.649s1.453.649 3.141.649s3.141-.649 3.141-.649z");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.i4ttorblq {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M21.199 19.859c-.015-.047-.426.141-.426.141l-1.846-2.362c.226-.405.49-1.073.49-1.904c0-1.241-.658-1.567-1.077-1.654v-.055a.31.31 0 0 0-.311-.311h-.059a.31.31 0 0 0-.311.311v.056c-.419.087-1.076.413-1.076 1.654c0 .848.275 1.528.504 1.93L15.328 20s-.359-.188-.375-.141s-.75 1.219-.75 1.219s1.562 1.02 3.797 1.02c2 0 3.873-1.02 3.873-1.02s-.658-1.172-.674-1.219m-2.105-4.078c0 .554-.221 1.157-.424 1.529l-.352-.45c.004-.02.022-.033.022-.054v-.728h.488l-.488-.488v-1.121c.494.174.754.719.754 1.312m-2.188 0c0-.594.26-1.138.753-1.312v1.121l-.488.488h.488v.728c0 .025.021.041.026.064l-.345.458c-.204-.37-.434-.982-.434-1.547");
}

.sex7xjoka {
  fill: var(--svg-color--00209f, #00209f);
  d: path("M32 5H4a4 4 0 0 0-4 4v4h36V9a4 4 0 0 0-4-4");
}

.vbxe0xtoi {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 13h36v10H0z");
}

.xcfhw0bzy {
  fill: var(--svg-color--009543, #009543);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
